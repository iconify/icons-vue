<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qa9oprbsr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qa9oprbsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:testicles-24px" /></template>
