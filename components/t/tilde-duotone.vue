<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dlf42bbdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dlf42bbdk primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:tilde-duotone" /></template>
