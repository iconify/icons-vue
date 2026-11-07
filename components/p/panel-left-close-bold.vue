<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bv-godbfy.css';
import '../../css/o/o-08tibye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bv-godbfy"/><path class="o-08tibye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:panel-left-close-bold" /></template>
