<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oqm9wbc2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":33,"height":33};
const content = `<path clip-rule="evenodd" class="oqm9wbc2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:okta" /></template>
