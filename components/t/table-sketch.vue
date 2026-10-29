<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/z/z3kvz9f2w.css';
import '../../css/k/kzr2ezdff.css';
import '../../css/y/yeo0byw9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="z3kvz9f2w"/><path class="kzr2ezdff"/><path class="yeo0byw9c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:table-sketch" /></template>
