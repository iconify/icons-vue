<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z82u35bbt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z82u35bbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:wallet-5-fill" /></template>
