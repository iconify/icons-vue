<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/blalr_7lp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="blalr_7lp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:square-minus-solid" /></template>
