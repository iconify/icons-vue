<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f9kl6cc3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="f9kl6cc3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:one-vesus-one-remix" /></template>
