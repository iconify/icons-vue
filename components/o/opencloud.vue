<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/exmrhmgxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="exmrhmgxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:opencloud" /></template>
