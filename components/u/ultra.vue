<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pu5troc5n.css';
import '../../css/u/unhe2tbbq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pu5troc5n"/><path class="unhe2tbbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:ultra" /></template>
