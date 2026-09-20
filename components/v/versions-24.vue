<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uawdfyvtp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uawdfyvtp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:versions-24" /></template>
