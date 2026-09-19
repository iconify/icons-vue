<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/adzt5lq3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="adzt5lq3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:stamp-filled" /></template>
