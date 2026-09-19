<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fm-tuvb1l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fm-tuvb1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:yeelight-cube2" /></template>
