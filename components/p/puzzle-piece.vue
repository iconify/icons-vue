<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fcm97eguq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fcm97eguq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:puzzle-piece" /></template>
