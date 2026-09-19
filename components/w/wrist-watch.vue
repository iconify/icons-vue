<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w3pqhgbsx.css';
import '../../css/o/obc0bdcuj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w3pqhgbsx"/><path class="obc0bdcuj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:wrist-watch" /></template>
