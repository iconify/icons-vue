<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/va8uaub1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="va8uaub1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:suspension-bolt" /></template>
