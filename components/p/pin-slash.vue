<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wpvnfvb8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wpvnfvb8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:pin-slash" /></template>
