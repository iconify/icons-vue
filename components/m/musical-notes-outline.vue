<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_5qwt2go.css';
import '../../css/b/b8j_7x21u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b_5qwt2go"/><path class="b8j_7x21u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:musical-notes-outline" /></template>
