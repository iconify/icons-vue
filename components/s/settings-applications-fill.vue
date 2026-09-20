<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jgcif9d1i.css';
import '../../css/g/gkg9z-_hv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jgcif9d1i"/><path clip-rule="evenodd" class="gkg9z-_hv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:settings-applications-fill" /></template>
