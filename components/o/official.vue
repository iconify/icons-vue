<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/btibzlb2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":352,"height":488};
const content = `<path class="btibzlb2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:official" /></template>
