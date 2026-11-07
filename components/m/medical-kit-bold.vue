<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k89onwb0c.css';
import '../../css/z/zlth73b-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k89onwb0c"/><path clip-rule="evenodd" class="zlth73b-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:medical-kit-bold" /></template>
