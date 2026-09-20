<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rc7hm0bsd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rc7hm0bsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:microscope-off" /></template>
