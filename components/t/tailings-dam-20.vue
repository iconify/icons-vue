<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gugafwbru.css';
import '../../css/p/pkpr5tboh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gugafwbru"/><path class="pkpr5tboh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tailings-dam-20" /></template>
