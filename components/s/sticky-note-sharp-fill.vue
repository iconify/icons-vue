<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aoyl7fb3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aoyl7fb3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:sticky-note-sharp-fill" /></template>
