<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pjsseubff.css';
import '../../css/p/p9m7uqziz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-secondary-layer pjsseubff"/><path class="duoicon-primary-layer p9m7uqziz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="duo-icons:message-2" /></template>
