<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dvq6_6b7x.css';
import '../../css/q/qxsh5ebmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-primary-layer dvq6_6b7x"/><path class="duoicon-secondary-layer qxsh5ebmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="duo-icons:smartwatch" /></template>
