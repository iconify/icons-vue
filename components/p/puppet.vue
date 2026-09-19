<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aldf9vb3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":335,"height":512};
const content = `<path class="aldf9vb3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:puppet" /></template>
