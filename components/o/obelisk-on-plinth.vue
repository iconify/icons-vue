<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bdo7bhahp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="bdo7bhahp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:obelisk-on-plinth" /></template>
