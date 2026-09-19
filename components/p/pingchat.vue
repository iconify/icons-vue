<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/edoc9w87l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":472,"height":488};
const content = `<path class="edoc9w87l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:pingchat" /></template>
