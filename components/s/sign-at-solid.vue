<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jhi9uibky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="jhi9uibky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:sign-at-solid" /></template>
