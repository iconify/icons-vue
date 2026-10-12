<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iz97go0-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iz97go0-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:waves-up" /></template>
