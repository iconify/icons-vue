<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oci2gci4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="oci2gci4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:unsplash-filled" /></template>
