<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bg1l3vbop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bg1l3vbop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:relation-many-to-one" /></template>
