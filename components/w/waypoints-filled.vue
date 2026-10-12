<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yo3s6ybnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yo3s6ybnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:waypoints-filled" /></template>
