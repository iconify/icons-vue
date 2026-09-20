<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bkii_8o6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="bkii_8o6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:tanuki-verified" /></template>
