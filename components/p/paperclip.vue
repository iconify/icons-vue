<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/smx2kur-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="smx2kur-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:paperclip" /></template>
