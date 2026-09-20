<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kybbu-9xb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kybbu-9xb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:panel-right-close-sharp" /></template>
