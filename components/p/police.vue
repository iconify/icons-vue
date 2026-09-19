<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s5pmp4sjw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":897,"height":1024};
const content = `<path class="s5pmp4sjw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:police" /></template>
