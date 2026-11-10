<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-w2z6epy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b-w2z6epy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:sos" /></template>
