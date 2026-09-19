<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pejt8hb4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":288,"height":512};
const content = `<path class="pejt8hb4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:neuter" /></template>
