<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hcx7xcdvz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hcx7xcdvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:walking-1" /></template>
