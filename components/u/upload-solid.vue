<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/laka9bcki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="laka9bcki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:upload-solid" /></template>
