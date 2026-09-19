<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/doex5ofaj.css';
import '../../css/o/om-12ci7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="doex5ofaj"/><path class="om-12ci7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:minimize-outline" /></template>
