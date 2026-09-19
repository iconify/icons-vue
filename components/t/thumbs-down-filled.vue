<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pb24y8btw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pb24y8btw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:thumbs-down-filled" /></template>
