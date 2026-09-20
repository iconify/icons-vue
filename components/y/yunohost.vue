<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b5g66wbkc.css';
import '../../css/u/uk5liicmj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b5g66wbkc"/><path class="uk5liicmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:yunohost" /></template>
