<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ngk_lkb8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ngk_lkb8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:wrap-arch-remix" /></template>
