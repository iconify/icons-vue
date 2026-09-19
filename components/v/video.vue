<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pwmk7icaf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="pwmk7icaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:video" /></template>
