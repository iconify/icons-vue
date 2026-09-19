<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zyhdx35wk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zyhdx35wk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:play-solid" /></template>
