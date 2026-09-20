<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kxd_4bb2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kxd_4bb2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:roller-paintbrush-remix" /></template>
