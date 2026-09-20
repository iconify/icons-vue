<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ivbiynbww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ivbiynbww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:podman" /></template>
