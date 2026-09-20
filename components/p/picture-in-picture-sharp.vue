<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/smrup5bzn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="smrup5bzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:picture-in-picture-sharp" /></template>
