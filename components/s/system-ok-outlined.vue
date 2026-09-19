<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/giek2mg0i.css';
import '../../css/g/gw53p_brw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="giek2mg0i"/><path class="gw53p_brw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:system-ok-outlined" /></template>
