<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/btm2enb5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-4,"top":-1};
const content = `<path class="btm2enb5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:pocket-watch" /></template>
