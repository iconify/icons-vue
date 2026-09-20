<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxox9ob4e.css';
import '../../css/c/cnvf9lbkm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zxox9ob4e"/><path class="cnvf9lbkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:social-facebook-duotone" /></template>
