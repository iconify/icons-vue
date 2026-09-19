<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="iiu1gqbvi"/><g class="n1mjunbsu"><path class="qwkvbnbzq"/><g transform="translate(-.119 .091)scale(.99858)" class="nctb2ac4r"><ellipse class="rvwaidbsq"/><ellipse class="s303ugb2n"/></g><g class="nctb2ac4r"><path class="iyoc47ypr"/><path class="qejzcp29e"/></g><g transform="translate(-.119 .091)scale(.99858)" class="nctb2ac4r"><ellipse class="w9cv1cbyr"/><ellipse class="n-te84brl"/></g></g><path class="lgop2r_1k"/><g transform="translate(-.119 .091)scale(.99858)" class="n1mjunbsu"><path class="r_i7nmbvt"/><ellipse class="t05oa-b-b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:sparkler" /></template>
<style>
.iiu1gqbvi {
  fill: var(--svg-color--0c567d, #0c567d);
  d: path("M64 56.926c0 3.775-3.226 6.898-7 6.898H7.327c-3.765 0-7.06-3.124-7.06-6.898V7.261c0-3.771 3.294-7.17 7.06-7.17H57c3.77 0 7 3.399 7 7.17z");
}

.iyoc47ypr {
  d: path("M58.847 23.756c0 2.238.334 4.053.748 4.053c.408 0 .744-1.815.744-4.053c0-2.24-.336-4.052-.744-4.052c-.414 0-.748 1.814-.748 4.052");
}

.lgop2r_1k {
  fill: var(--svg-color--fff, #fff);
  d: path("M24.995 22.977c-.932.434-3.502-3.143-5.744-7.998c-2.24-4.842-3.305-9.116-2.37-9.55c.932-.43 3.502 3.146 5.743 7.989c2.242 4.85 3.303 9.121 2.371 9.555M46.8 5.433c-.931-.434-3.499 3.144-5.743 7.989c-2.24 4.842-3.304 9.117-2.368 9.551c.931.429 3.5-3.147 5.743-7.988c2.24-4.85 3.301-9.12 2.368-9.555");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.n-te84brl {
  cx: 4.277px;
  cy: 45.869px;
  rx: 4.058px;
  ry: 0.745px;
}

.n1mjunbsu {
  fill: var(--svg-color--fff, #fff);
}

.nctb2ac4r {
  opacity: var(--svg-opacity--0-8, 0.8);
}

.qejzcp29e {
  d: path("M59.592 24.5c2.235 0 4.05-.331 4.05-.744c0-.412-1.814-.744-4.05-.744c-2.24 0-4.056.332-4.056.744c0 .413 1.816.744 4.056.744");
}

.qwkvbnbzq {
  d: path("M52.846 39.046c0 10.682-9.27 19.343-20.705 19.343c-11.43 0-20.704-8.66-20.704-19.343S20.71 19.704 32.14 19.704c11.435 0 20.705 8.659 20.705 19.342");
  opacity: var(--svg-opacity--0-7, 0.7);
}

.r_i7nmbvt {
  d: path("m32.3 49.27l-8.2 7.3l.814-10.719l-11.04-1.621l9.219-6.07l-5.571-9.319l10.681 3.147L32.303 0l4.103 31.988l10.687-3.147l-5.573 9.319l9.214 6.07l-11.04 1.621l.812 10.719z");
  opacity: var(--svg-opacity--0-8, 0.8);
}

.rvwaidbsq {
  cx: 5.02px;
  cy: 10.938px;
  rx: 0.746px;
  ry: 4.058px;
}

.s303ugb2n {
  cx: 5.02px;
  cy: 10.938px;
  rx: 4.056px;
  ry: 0.746px;
}

.t05oa-b-b {
  cx: 32.3px;
  cy: 40.792px;
  opacity: var(--svg-opacity--0-8, 0.8);
  rx: 10.921px;
  ry: 10.202px;
}

.w9cv1cbyr {
  cx: 4.276px;
  cy: 45.871px;
  rx: 0.746px;
  ry: 4.057px;
}

</style>
