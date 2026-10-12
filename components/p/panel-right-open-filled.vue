<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ucnu-4ubw.css';
import '../../css/n/ndqjaugsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ucnu-4ubw"/><path class="ndqjaugsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:panel-right-open-filled" /></template>
