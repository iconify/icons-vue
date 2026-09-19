<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vjp588bse.css';
import '../../css/y/yas-v_bpy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vjp588bse"/><path class="yas-v_bpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:tennis-ball-alt-filled" /></template>
