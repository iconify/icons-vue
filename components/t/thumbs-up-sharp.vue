<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z1cbfwy3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z1cbfwy3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:thumbs-up-sharp" /></template>
