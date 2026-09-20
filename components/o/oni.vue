<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g3mjhacsa.css';
import '../../css/o/odewqcbbi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g3mjhacsa"/><path class="odewqcbbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:oni" /></template>
