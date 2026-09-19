<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gyxc17_eu.css';
import '../../css/f/fg7w486wz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gyxc17_eu"/><path class="fg7w486wz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:microphone-outline" /></template>
