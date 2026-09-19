<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ccyq5bk1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ccyq5bk1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:ship" /></template>
