<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jgz-nos8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jgz-nos8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:street-sign-solid" /></template>
