<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qs-hjhwcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:multimodal-hand-eye-outline-sharp" /></template>
<style>
.qs-hjhwcu {
  fill: currentColor;
  d: path("M11.154 21.48H6.652l-5.09-5.076l1.004-1.054l2.78.652V7.5h1v9.825l-3.238-.815l3.933 3.97h4.113q1.031 0 1.766-.733q.734-.735.734-1.766v-3.673h1v3.673q0 1.457-1.021 2.478t-2.48 1.022m-3.037-6.423v-4.52h1v4.52zm2.769 0v-3.135h1v3.135zm.269 5.423H7.67zm4.98-10.558q-1.832 0-3.382-.94T10.269 6.46q.933-1.58 2.483-2.52T16.135 3t3.382.94T22 6.463q-.933 1.58-2.483 2.52q-1.55.941-3.383.941m2.62-1.67q1.234-.668 2.073-1.791q-.839-1.123-2.07-1.793T16.137 4t-2.623.67t-2.072 1.792q.839 1.123 2.07 1.792t2.62.669t2.623-.67m-3.327-1.082q-.294-.291-.294-.707t.291-.71q.292-.292.707-.292q.416 0 .71.29t.293.707t-.292.71t-.706.293t-.709-.291");
}

</style>
