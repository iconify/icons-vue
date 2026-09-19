<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h1crshb5u.css';
import '../../css/s/sihn2yb6f.css';
import '../../css/h/hk3z8gb_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="h1crshb5u"/><circle class="sihn2yb6f"/><circle class="hk3z8gb_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:root-open" /></template>
