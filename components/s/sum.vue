<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xi58lbbar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xi58lbbar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:sum" /></template>
