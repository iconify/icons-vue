<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ziblf8w-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ziblf8w-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:smiley-devil-outline" /></template>
