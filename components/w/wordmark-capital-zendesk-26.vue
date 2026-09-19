<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u3a8fpbxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":87,"height":26};
const content = `<path class="u3a8fpbxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:wordmark-capital-zendesk-26" /></template>
