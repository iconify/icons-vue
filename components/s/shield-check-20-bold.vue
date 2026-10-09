<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p4bzr0bap.css';
import '../../css/z/z_bjwrbux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="p4bzr0bap"/><path class="z_bjwrbux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:shield-check-20-bold" /></template>
