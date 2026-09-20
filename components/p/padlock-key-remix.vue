<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oha-rb4et.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="oha-rb4et"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:padlock-key-remix" /></template>
