<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w7h9zxncv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w7h9zxncv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:plug-connect-filled" /></template>
