<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iinodqs4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iinodqs4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:text-footnote" /></template>
