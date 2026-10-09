<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b52to0bjp.css';
import '../../css/p/pfj9i6b-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="b52to0bjp"/><path class="pfj9i6b-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:solar-thermal-20-bold" /></template>
