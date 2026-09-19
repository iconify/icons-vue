<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q367x2bks.css';
import '../../css/a/ae_9512ms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q367x2bks"/><path class="ae_9512ms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:tablet-landscape" /></template>
