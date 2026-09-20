<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/regj2beml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="regj2beml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-kneeling-praying" /></template>
