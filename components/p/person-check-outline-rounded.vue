<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u9-hz-bug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:person-check-outline-rounded" /></template>
<style>
.u9-hz-bug {
  fill: currentColor;
  d: path("m17.55 9.887l3.89-3.897q.146-.146.347-.146t.367.146t.156.357t-.156.357l-4.038 4.019q-.243.243-.566.243t-.565-.243L15.07 8.809q-.146-.145-.155-.337q-.01-.191.155-.357q.146-.146.354-.146t.354.146zm-10.673.62Q6 9.632 6 8.386t.877-2.123Q7.754 5.385 9 5.385t2.123.877T12 8.385t-.877 2.123T9 11.385t-2.123-.877M2 17.577v-.608q0-.619.36-1.158q.361-.54.97-.838q1.416-.679 2.834-1.018q1.417-.34 2.836-.34t2.837.34t2.832 1.018q.61.298.97.838q.361.539.361 1.158v.608q0 .44-.299.74q-.299.298-.74.298H3.04q-.441 0-.74-.299t-.3-.739m1 .039h12v-.647q0-.332-.215-.625q-.214-.292-.593-.494q-1.234-.598-2.542-.916T9 14.616t-2.65.318t-2.542.916q-.38.202-.593.494Q3 16.637 3 16.97zm7.413-7.819Q11 9.21 11 8.385t-.587-1.413T9 6.385t-1.412.587T7 8.385t.588 1.412T9 10.385t1.413-.588M9 8.385");
}

</style>
