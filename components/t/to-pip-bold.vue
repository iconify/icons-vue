<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/udz5nqb7v.css';
import '../../css/n/nf63yr-ml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="udz5nqb7v"/><path clip-rule="evenodd" class="nf63yr-ml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:to-pip-bold" /></template>
