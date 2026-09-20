<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uzvbfpb6b.css';
import '../../css/b/b81wimuvn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uzvbfpb6b"/><path class="b81wimuvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:maloja" /></template>
