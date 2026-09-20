<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gu78stbua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gu78stbua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:simplelogin" /></template>
