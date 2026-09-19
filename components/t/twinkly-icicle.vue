<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jvu2yvxqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jvu2yvxqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:twinkly-icicle" /></template>
