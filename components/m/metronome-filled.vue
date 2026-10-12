<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p3yjsomuv.css';
import '../../css/m/msszb5b2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p3yjsomuv"/><path class="msszb5b2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:metronome-filled" /></template>
