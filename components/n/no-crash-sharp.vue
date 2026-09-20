<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wvx0s7pcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:no-crash-sharp" /></template>
<style>
.wvx0s7pcw {
  fill: currentColor;
  d: path("M12 5.639L9.887 3.55l.688-.713L12 4.26L15.55.71l.688.689zM4 23v-7.846L6.162 9h11.677L20 15.154V23h-1.23v-2H5.23v2zm1.416-8.846h13.169L17.112 10H6.889zm2.011 4.538q.467 0 .79-.326q.322-.327.322-.794q0-.466-.327-.788q-.327-.323-.793-.323q-.467 0-.79.327q-.321.327-.321.793q0 .467.326.79q.327.321.793.321m9.155 0q.466 0 .788-.326q.322-.327.322-.794q0-.466-.326-.788q-.327-.323-.793-.323q-.467 0-.79.327q-.321.327-.321.793q0 .467.326.79q.327.321.794.321");
}

</style>
