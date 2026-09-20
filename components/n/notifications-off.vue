<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/krtwebc9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="krtwebc9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:notifications-off" /></template>
