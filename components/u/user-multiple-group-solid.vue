<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pbh_n3bjd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="pbh_n3bjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:user-multiple-group-solid" /></template>
