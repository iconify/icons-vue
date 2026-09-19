<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rw_7son6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="rw_7son6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:user-tie" /></template>
