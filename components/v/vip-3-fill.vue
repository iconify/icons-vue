<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kbo8fs4al.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kbo8fs4al"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:vip-3-fill" /></template>
