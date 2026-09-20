<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dzq4r8brf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dzq4r8brf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:youtube" /></template>
