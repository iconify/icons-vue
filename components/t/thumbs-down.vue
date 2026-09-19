<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/blzfdpb2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="blzfdpb2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:thumbs-down" /></template>
