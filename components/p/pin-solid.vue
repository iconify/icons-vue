<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o2ljld0iz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o2ljld0iz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:pin-solid" /></template>
