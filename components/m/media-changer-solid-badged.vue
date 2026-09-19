<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tokrscowc.css';
import '../../css/l/lmf0ecbhq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="tokrscowc"/><circle class="lmf0ecbhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:media-changer-solid-badged" /></template>
