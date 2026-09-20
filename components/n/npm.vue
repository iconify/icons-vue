<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ptj-h9xbd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ptj-h9xbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:npm" /></template>
