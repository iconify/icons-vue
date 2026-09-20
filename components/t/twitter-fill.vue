<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gef5ck7od.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gef5ck7od"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:twitter-fill" /></template>
