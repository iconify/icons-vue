<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dy1i_6bbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="dy1i_6bbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:thumbs-up-fill" /></template>
