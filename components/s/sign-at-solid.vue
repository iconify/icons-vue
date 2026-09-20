<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/knsk67hid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="knsk67hid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:sign-at-solid" /></template>
