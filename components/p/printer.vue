<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ygwxw340a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ygwxw340a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:printer" /></template>
