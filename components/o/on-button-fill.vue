<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l84sn-bxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l84sn-bxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:on-button-fill" /></template>
