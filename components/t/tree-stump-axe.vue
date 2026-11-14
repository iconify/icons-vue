<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kzkreej_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:tree-stump-axe" /></template>
<style>
.kzkreej_u {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m12.366 7.406l.707 3.004q4.177.503 4.177 2.59v5.823l.921 1.842q.079.158.079.335q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-15q-.177 0-.335-.079q-.134-.067-.232-.18q-.097-.112-.145-.254q-.047-.141-.036-.29q.01-.149.077-.282l.921-1.842v-5.824q.002-2.123 4.325-2.606l1.746-3.712q.046-.097.116-.177t.161-.137t.193-.087t.209-.03h1.823l8.842-4.421q.066-.033.137-.052q.071-.02.145-.025t.147.004t.143.032t.134.06t.12.085t.101.107t.079.125q.067.133.077.282q.011.149-.036.29q-.048.142-.145.254q-.098.113-.232.18zM10 10.25q.795 0 1.502.033l-.596-2.533h-.93L8.79 10.271q.577-.021 1.21-.021M4.25 19q0 .177-.079.335l-.457.915h12.572l-.457-.915q-.079-.158-.079-.335v-4.067q-1.798.817-5.75.817t-5.75-.817z");
}

</style>
