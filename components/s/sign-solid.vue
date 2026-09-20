<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lwm14abzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="lwm14abzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:sign-solid" /></template>
