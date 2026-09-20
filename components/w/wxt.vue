<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/df31ufblk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="df31ufblk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:wxt" /></template>
