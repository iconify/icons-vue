<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u3e9pfbec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u3e9pfbec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:volume-minus-sharp" /></template>
