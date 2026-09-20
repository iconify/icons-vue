<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/evf4ks.css';
import '../../css/p/psjrum.css';
import '../../css/j/j3df0o.css';
import '../../css/u/uzlaax.css';
import '../../css/t/t5hnje.css';
import '../../css/s/so-from-66.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="evf4ks psjrum"/><path class="evf4ks j3df0o"/><path class="evf4ks uzlaax"/><path class="evf4ks t5hnje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:spotify" /></template>
