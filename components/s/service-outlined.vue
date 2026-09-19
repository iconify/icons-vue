<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g0s97_4wn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g0s97_4wn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:service-outlined" /></template>
