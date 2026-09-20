<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cbn3z8r9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cbn3z8r9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:yen-octagon" /></template>
