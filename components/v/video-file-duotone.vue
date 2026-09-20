<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a9h3i4b2f.css';
import '../../css/a/a7grcu7de.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a9h3i4b2f"/><path class="a7grcu7de"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:video-file-duotone" /></template>
