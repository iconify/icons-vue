<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wp4_c_vog.css';
import '../../css/p/pswt3mbkl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wp4_c_vog"/><path clip-rule="evenodd" class="pswt3mbkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:sun-solid" /></template>
