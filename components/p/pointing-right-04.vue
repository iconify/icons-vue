<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wvxc6dbxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wvxc6dbxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:pointing-right-04" /></template>
