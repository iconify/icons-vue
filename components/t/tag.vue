<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bob09ob5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1000,"height":1000};
const content = `<path class="bob09ob5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="websymbol:tag" /></template>
