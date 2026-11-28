<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dsyie6gxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dsyie6gxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:point-up-solid" /></template>
