<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ada_u3u5b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="ada_u3u5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:photo-slash-20-solid" /></template>
