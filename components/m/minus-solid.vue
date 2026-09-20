<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aao71moyn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aao71moyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:minus-solid" /></template>
