<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wone3cgvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wone3cgvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:square-check-solid" /></template>
