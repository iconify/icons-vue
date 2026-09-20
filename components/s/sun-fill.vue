<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xck076b8z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xck076b8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:sun-fill" /></template>
