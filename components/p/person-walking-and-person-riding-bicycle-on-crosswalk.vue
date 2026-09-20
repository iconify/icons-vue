<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z5i4e-nou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="z5i4e-nou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-walking-and-person-riding-bicycle-on-crosswalk" /></template>
